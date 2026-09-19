<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-_m7sbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b-_m7sbyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:shopping-bag-fill" {...props}></Icon>
