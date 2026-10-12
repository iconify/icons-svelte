<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjhfl-nlv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bjhfl-nlv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:square-brackets" {...props}></Icon>
