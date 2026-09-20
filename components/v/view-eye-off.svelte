<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv2l60z2l.css';
import '../../css/s/sbpa77b-h.css';
import '../../css/o/onghmnteu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nv2l60z2l"/><path class="sbpa77b-h"/><path class="onghmnteu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:view-eye-off" {...props}></Icon>
