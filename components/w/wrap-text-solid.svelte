<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tew7bmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y9tew7bmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:wrap-text-solid" {...props}></Icon>
