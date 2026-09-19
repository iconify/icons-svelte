<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab5hjefrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ab5hjefrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:triangle" {...props}></Icon>
