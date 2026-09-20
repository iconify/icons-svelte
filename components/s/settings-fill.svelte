<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht4ivw9gu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ht4ivw9gu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:settings-fill" {...props}></Icon>
