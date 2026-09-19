<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhvsifbll.css';
import '../../css/k/kwokvsbhf.css';
import '../../css/o/oli25tbif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fhvsifbll"/><path class="kwokvsbhf"/><path class="oli25tbif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:stackdriver" {...props}></Icon>
