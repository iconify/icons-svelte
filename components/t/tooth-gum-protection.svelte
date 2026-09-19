<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u59jxfb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u59jxfb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:tooth-gum-protection" {...props}></Icon>
