<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te-6zluiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="te-6zluiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:syringe" {...props}></Icon>
