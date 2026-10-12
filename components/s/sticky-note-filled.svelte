<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aaqykgbsd.css';
import '../../css/n/nbhl3j1uc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aaqykgbsd"/><path class="nbhl3j1uc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:sticky-note-filled" {...props}></Icon>
