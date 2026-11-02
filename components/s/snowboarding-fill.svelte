<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sal6xlgzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sal6xlgzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:snowboarding-fill" {...props}></Icon>
