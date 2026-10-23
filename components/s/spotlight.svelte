<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_9cmlbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_9cmlbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:spotlight" {...props}></Icon>
