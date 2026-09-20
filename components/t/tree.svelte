<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-k8phbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="v-k8phbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:tree" {...props}></Icon>
