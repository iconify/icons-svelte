<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkmq48bsn.css';
import '../../css/q/qd1ggccdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mkmq48bsn"/><path class="qd1ggccdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:share-box-outline" {...props}></Icon>
