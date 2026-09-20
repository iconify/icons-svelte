<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-8wnyb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k-8wnyb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:table-sharp-fill" {...props}></Icon>
