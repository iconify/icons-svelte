<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wim4ymbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wim4ymbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:unlock-filled" {...props}></Icon>
