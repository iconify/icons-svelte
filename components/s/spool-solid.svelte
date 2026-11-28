<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkq50_b7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tkq50_b7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:spool-solid" {...props}></Icon>
