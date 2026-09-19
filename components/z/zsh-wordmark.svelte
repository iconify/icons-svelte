<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0omkob4z.css';
import '../../css/q/qx5t5kjwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="m0omkob4z"/><path class="qx5t5kjwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:zsh-wordmark" {...props}></Icon>
