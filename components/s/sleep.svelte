<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhk_xi9ht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mhk_xi9ht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:sleep" {...props}></Icon>
