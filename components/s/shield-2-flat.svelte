<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngo_95bsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ngo_95bsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:shield-2-flat" {...props}></Icon>
