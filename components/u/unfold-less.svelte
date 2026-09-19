<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uh8z32gqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uh8z32gqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:unfold-less" {...props}></Icon>
