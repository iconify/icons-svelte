<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9-e4db2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9-e4db2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:table" {...props}></Icon>
