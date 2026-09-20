<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqg1arbtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pqg1arbtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:terminal-alt-fill" {...props}></Icon>
