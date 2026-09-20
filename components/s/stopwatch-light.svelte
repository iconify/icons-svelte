<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c42wbbbmv.css';
import '../../css/a/a9mdu8gjb.css';
import '../../css/u/upbnhsbyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c42wbbbmv"/><path class="a9mdu8gjb"/><path clip-rule="evenodd" class="upbnhsbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:stopwatch-light" {...props}></Icon>
