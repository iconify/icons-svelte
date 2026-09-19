<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aufc9acsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aufc9acsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:wallet-outline" {...props}></Icon>
