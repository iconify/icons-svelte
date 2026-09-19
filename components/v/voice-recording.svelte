<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-f7jlbzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h-f7jlbzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:voice-recording" {...props}></Icon>
