<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufmb-0o7z.css';
import '../../css/t/tnufrjb2z.css';
import '../../css/f/f2gaakbew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufmb-0o7z"/><path clip-rule="evenodd" class="tnufrjb2z"/><path clip-rule="evenodd" class="f2gaakbew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:target-filled" {...props}></Icon>
