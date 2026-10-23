<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj2on39or.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aj2on39or"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:user-shield" {...props}></Icon>
