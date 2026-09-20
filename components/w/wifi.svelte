<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aetlc5bek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aetlc5bek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:wifi" {...props}></Icon>
