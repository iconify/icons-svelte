<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/naysjv-ce.css';
import '../../css/g/g-mtj-z5m.css';
import '../../css/i/iqtg16bzl.css';
import '../../css/s/skp8tjssj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="naysjv-ce"/><path class="g-mtj-z5m"/><path class="iqtg16bzl"/><path class="skp8tjssj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:user-star-duotone" {...props}></Icon>
