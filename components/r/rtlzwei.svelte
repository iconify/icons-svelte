<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncixj9qwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ncixj9qwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:rtlzwei" {...props}></Icon>
