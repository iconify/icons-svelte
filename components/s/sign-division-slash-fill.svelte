<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n12cj6bru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n12cj6bru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-division-slash-fill" {...props}></Icon>
