<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_3llnbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="s_3llnbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:snowflake-6" {...props}></Icon>
