<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj008nblr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hj008nblr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:telegram-outline" {...props}></Icon>
