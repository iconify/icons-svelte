<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkiig2blz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hkiig2blz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:youtube" {...props}></Icon>
