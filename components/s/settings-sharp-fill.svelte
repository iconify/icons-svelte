<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vryog_buw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vryog_buw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:settings-sharp-fill" {...props}></Icon>
