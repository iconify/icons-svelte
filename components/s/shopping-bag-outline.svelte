<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npyt5pblr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="npyt5pblr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:shopping-bag-outline" {...props}></Icon>
