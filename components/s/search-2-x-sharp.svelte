<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb5mbg0ow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lb5mbg0ow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:search-2-x-sharp" {...props}></Icon>
