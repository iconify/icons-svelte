<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvxw2nvec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dvxw2nvec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-plus-sharp-fill" {...props}></Icon>
