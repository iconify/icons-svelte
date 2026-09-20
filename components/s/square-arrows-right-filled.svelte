<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eeo0agb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eeo0agb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:square-arrows-right-filled" {...props}></Icon>
