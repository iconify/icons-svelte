<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq7wydr-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sq7wydr-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-stop-sharp-fill" {...props}></Icon>
