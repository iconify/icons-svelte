<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mktlpu4xk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="mktlpu4xk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:taxi-stand" {...props}></Icon>
