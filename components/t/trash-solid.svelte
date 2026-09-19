<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4he1pszq.css';
import '../../css/a/ag8l5kbvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4he1pszq"/><path clip-rule="evenodd" class="ag8l5kbvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:trash-solid" {...props}></Icon>
