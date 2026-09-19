<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpay17boa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="hpay17boa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:users-slash" {...props}></Icon>
