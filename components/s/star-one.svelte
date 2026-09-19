<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8brmzbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="b8brmzbrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:star-one" {...props}></Icon>
