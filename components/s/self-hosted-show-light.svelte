<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asj-_acvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="asj-_acvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:self-hosted-show-light" {...props}></Icon>
