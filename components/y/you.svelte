<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgbx9bfba.css';
import '../../css/l/l1tfhcbvb.css';
import '../../css/f/f6kx-ccba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgbx9bfba"/><path class="l1tfhcbvb"/><path class="f6kx-ccba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:you" {...props}></Icon>
