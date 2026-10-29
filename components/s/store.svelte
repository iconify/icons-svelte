<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb07q-bxa.css';
import '../../css/j/j3skc-b5v.css';
import '../../css/c/crqmprq7t.css';
import '../../css/e/ejtpq101k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cb07q-bxa wm-k"/><path class="j3skc-b5v wm-a"/><path class="crqmprq7t wm-k"/><path class="ejtpq101k wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:store" {...props}></Icon>
