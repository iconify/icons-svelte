<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud_9sccoj.css';
import '../../css/c/c5p-nqbdf.css';
import '../../css/w/wc2m4bc5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ud_9sccoj"/><path class="c5p-nqbdf"/><path class="wc2m4bc5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-field-focus-outline" {...props}></Icon>
