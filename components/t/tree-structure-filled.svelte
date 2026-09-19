<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekh_09cjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ekh_09cjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:tree-structure-filled" {...props}></Icon>
