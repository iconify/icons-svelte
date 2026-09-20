<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txxcw59-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txxcw59-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:skype-alt" {...props}></Icon>
