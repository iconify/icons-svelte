<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/i/i_-8rn_4z.css';
import '../../css/v/v_fpkcbui.css';
import '../../css/k/kcex68bds.css';
import '../../css/o/ofkzbwboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path clip-rule="evenodd" class="i_-8rn_4z"/><path class="v_fpkcbui"/><path class="kcex68bds"/><path class="ofkzbwboa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:wallet" {...props}></Icon>
