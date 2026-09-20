<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avfrtjb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avfrtjb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:verified-check-fill" {...props}></Icon>
