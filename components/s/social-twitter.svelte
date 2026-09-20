<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl5r9mbkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nl5r9mbkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:social-twitter" {...props}></Icon>
