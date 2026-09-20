<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhi9uibky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jhi9uibky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:sign-at-solid" {...props}></Icon>
