<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7zwfz7lk.css';
import '../../css/n/nbhl3j1uc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t7zwfz7lk"/><path class="nbhl3j1uc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:sticker-filled" {...props}></Icon>
