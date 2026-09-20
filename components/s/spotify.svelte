<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw451mrxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nw451mrxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:spotify" {...props}></Icon>
