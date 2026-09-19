<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwkrfjg0w.css';
import '../../css/k/ks1061b-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwkrfjg0w"/><path class="ks1061b-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:sofa-filled" {...props}></Icon>
