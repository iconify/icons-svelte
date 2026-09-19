<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr0u-obfa.css';
import '../../css/q/qoypj_b7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":16};
const content = `<path class="mr0u-obfa"/><path class="qoypj_b7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:text" {...props}></Icon>
