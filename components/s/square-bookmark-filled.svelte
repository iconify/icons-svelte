<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvt3gewoh.css';
import '../../css/d/doecxd77k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvt3gewoh"/><path class="doecxd77k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-bookmark-filled" {...props}></Icon>
