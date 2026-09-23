<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6v10ib0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6v10ib0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:variable-sharp-fill" {...props}></Icon>
