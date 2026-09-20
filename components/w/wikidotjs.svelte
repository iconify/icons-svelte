<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtrc044zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gtrc044zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:wikidotjs" {...props}></Icon>
