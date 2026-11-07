<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgn7bubwt.css';
import '../../css/u/u-3cpkh9t.css';
import '../../css/f/fog6w8bnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgn7bubwt"/><path class="u-3cpkh9t"/><path class="fog6w8bnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rows-3-bold" {...props}></Icon>
