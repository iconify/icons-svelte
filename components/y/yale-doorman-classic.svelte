<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k52384bvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k52384bvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:yale-doorman-classic" {...props}></Icon>
