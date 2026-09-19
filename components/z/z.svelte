<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb9ltdbub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":520,"height":654};
const content = `<path class="wb9ltdbub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:z" {...props}></Icon>
