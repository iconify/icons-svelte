<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1y0covbn.css';
import '../../css/i/i_z5csbpk.css';
import '../../css/f/f3not4nii.css';
import '../../css/p/pv9i0lw2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1y0covbn"/><path class="i_z5csbpk"/><path class="f3not4nii"/><path class="pv9i0lw2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:storage-class-outlined" {...props}></Icon>
