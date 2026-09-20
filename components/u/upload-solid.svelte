<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/laka9bcki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="laka9bcki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:upload-solid" {...props}></Icon>
