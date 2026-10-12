<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9gf4ebfj.css';
import '../../css/h/hnvtq9frh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9gf4ebfj"/><path clip-rule="evenodd" class="hnvtq9frh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:washing-machine-filled" {...props}></Icon>
