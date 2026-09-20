<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kiuggabrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kiuggabrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:squidoo-logo-block" {...props}></Icon>
