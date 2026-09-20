<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdzggabux.css';
import '../../css/y/y9rqo7u8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="sdzggabux"/><path class="y9rqo7u8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:text-format" {...props}></Icon>
