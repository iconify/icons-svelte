<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbrtl5bbj.css';
import '../../css/q/qvl5apb0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="bbrtl5bbj"/><path class="qvl5apb0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:timer" {...props}></Icon>
