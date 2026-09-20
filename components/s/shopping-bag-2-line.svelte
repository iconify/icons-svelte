<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avt3a6b-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avt3a6b-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shopping-bag-2-line" {...props}></Icon>
