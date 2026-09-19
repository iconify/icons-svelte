<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzi7qo5ju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzi7qo5ju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:share-ios-export" {...props}></Icon>
