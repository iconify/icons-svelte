<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edhfktowk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="edhfktowk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:vision-pro" {...props}></Icon>
