<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw9jp9b-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tw9jp9b-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:share-android-24" {...props}></Icon>
