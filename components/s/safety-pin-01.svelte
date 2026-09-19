<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/r/r3v884hcy.css';
import '../../css/g/g1ere0j-x.css';
import '../../css/y/y7ql6fbwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r3v884hcy"/><circle class="g1ere0j-x"/><path class="y7ql6fbwj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:safety-pin-01" {...props}></Icon>
