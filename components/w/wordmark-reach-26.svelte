<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyqkh4byn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":61,"height":26};
const content = `<path class="kyqkh4byn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:wordmark-reach-26" {...props}></Icon>
