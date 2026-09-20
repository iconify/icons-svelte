<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j01r4uprb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j01r4uprb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:share-outline" {...props}></Icon>
