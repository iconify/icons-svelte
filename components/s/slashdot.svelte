<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw9em7lpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tw9em7lpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:slashdot" {...props}></Icon>
