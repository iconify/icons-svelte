<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdwwaccwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mdwwaccwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ruler-angular-outline" {...props}></Icon>
