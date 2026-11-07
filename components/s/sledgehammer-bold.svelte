<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qaeey4wki.css';
import '../../css/v/v1sgvk7sy.css';
import '../../css/o/oq1kt7b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qaeey4wki"/><path class="v1sgvk7sy"/><path class="oq1kt7b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sledgehammer-bold" {...props}></Icon>
