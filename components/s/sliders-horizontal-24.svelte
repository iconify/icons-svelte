<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf53lvbya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pf53lvbya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:sliders-horizontal-24" {...props}></Icon>
