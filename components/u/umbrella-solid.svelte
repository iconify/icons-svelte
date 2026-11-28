<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o96x5_bdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o96x5_bdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:umbrella-solid" {...props}></Icon>
