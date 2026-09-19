<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld-pkh_3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ld-pkh_3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:share-android" {...props}></Icon>
