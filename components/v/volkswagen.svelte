<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duvaw7d9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duvaw7d9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:volkswagen" {...props}></Icon>
