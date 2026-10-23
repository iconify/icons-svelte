<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hr8ti0b8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hr8ti0b8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:squirrel" {...props}></Icon>
