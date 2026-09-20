<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9gnfxb8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y9gnfxb8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:trading-pattern-up-bold" {...props}></Icon>
