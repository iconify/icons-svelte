<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjisd8szm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tjisd8szm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:vertical-switch-long-light" {...props}></Icon>
