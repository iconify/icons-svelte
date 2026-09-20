<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncrdy1llp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ncrdy1llp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:shield-minus-sharp-fill" {...props}></Icon>
