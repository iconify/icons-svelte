<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk0r7efoy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dk0r7efoy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:square-outline" {...props}></Icon>
