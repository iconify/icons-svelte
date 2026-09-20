<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd5m9ubhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nd5m9ubhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:user-check-validate-solid" {...props}></Icon>
