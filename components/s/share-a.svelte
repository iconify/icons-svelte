<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr2-00fdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":29,"height":24};
const content = `<path class="sr2-00fdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:share-a" {...props}></Icon>
