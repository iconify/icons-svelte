<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qiyj-2b5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qiyj-2b5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:tether" {...props}></Icon>
