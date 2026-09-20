<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exff0k9xs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exff0k9xs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:seafile" {...props}></Icon>
