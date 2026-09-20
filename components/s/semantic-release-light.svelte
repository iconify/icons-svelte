<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhafzrngg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":300};
const content = `<path class="yhafzrngg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:semantic-release-light" {...props}></Icon>
