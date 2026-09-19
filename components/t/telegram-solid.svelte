<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_4pe5bal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d_4pe5bal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:telegram-solid" {...props}></Icon>
