<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbkp-y9iw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbkp-y9iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:waves-fill-round" {...props}></Icon>
