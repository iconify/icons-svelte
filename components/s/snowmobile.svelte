<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ho7y_mbjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="ho7y_mbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:snowmobile" {...props}></Icon>
