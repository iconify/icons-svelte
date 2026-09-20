<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eoj8bc9hp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eoj8bc9hp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:smug-mug-logo-block" {...props}></Icon>
