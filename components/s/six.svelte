<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kw59hezlg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kw59hezlg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:six" {...props}></Icon>
