<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qoe8j9jwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qoe8j9jwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:star-outline" {...props}></Icon>
