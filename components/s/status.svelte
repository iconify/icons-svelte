<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nii0p1blk.css';
import '../../css/h/h631kg9bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nii0p1blk"/><circle class="h631kg9bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:status" {...props}></Icon>
