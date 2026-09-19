<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar8e79b7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ar8e79b7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:shopping-bag-plus" {...props}></Icon>
