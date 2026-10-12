<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsfup6hkd.css';
import '../../css/m/mwsqe_7mb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dsfup6hkd"/><path class="mwsqe_7mb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:virus-off-filled" {...props}></Icon>
