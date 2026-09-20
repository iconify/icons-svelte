<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8hrmeb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q8hrmeb-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:scissors-solid" {...props}></Icon>
