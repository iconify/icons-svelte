<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h96oc06ai.css';
import '../../css/s/srkn7eb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h96oc06ai"/><path class="srkn7eb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:stethoscope-alt" {...props}></Icon>
