<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnbntv8lb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":685,"height":717};
const content = `<path class="hnbntv8lb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:sns" {...props}></Icon>
