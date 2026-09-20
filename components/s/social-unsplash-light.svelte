<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e98mnlbjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e98mnlbjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:social-unsplash-light" {...props}></Icon>
