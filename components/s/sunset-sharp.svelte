<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnjz_aczh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnjz_aczh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:sunset-sharp" {...props}></Icon>
