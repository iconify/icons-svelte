<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uoel2t9wc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uoel2t9wc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:school-lock-outline" {...props}></Icon>
